<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjb94vbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjb94vbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-new-outline" /></template>
