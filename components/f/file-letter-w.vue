<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl6idlb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bl6idlb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-letter-w" /></template>
