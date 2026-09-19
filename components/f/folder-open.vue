<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acp9e5g1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="acp9e5g1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:folder-open" /></template>
