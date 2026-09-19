<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pguputbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pguputbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:branches-right-arrow-right" /></template>
