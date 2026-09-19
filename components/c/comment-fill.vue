<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtb49rb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xtb49rb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:comment-fill" /></template>
