<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf8y5ebgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf8y5ebgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:folder" /></template>
