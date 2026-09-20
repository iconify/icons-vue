<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9q2oebck.css';
import '../../css/g/gnnib_beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x9q2oebck"/><path clip-rule="evenodd" class="gnnib_beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-delete-file" /></template>
