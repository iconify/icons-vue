<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2kpl4oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp2kpl4oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book-minus-line" /></template>
