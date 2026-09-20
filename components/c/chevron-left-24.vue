<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opby1ibzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opby1ibzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-left-24" /></template>
