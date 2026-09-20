<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbj_egiqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bbj_egiqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bolt" /></template>
