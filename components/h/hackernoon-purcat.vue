<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq3n7ab0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq3n7ab0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:hackernoon-purcat" /></template>
