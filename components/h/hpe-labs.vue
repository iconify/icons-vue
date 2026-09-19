<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq7iz5vvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7iz5vvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:hpe-labs" /></template>
