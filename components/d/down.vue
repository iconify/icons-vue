<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8vgp4bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":7};
const content = `<path class="b8vgp4bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:down" /></template>
