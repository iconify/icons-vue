<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ildxedcli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ildxedcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hush" /></template>
