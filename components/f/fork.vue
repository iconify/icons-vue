<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3px4fbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3px4fbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fork" /></template>
