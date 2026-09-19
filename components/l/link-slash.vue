<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwx_n2boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwx_n2boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:link-slash" /></template>
