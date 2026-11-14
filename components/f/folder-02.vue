<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwcynvbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcynvbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-02" /></template>
