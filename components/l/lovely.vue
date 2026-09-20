<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r777ilc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r777ilc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lovely" /></template>
