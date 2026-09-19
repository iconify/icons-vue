<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt2w33fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt2w33fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bone-02" /></template>
