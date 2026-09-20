<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s52zm8mgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s52zm8mgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bone" /></template>
