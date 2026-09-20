<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaa3sjb5u.css';
import '../../css/w/wpnzcqdzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa3sjb5u"/><path class="wpnzcqdzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-relates-to-24" /></template>
