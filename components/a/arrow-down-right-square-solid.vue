<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi1xqabvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi1xqabvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-right-square-solid" /></template>
