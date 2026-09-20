<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw25wvpgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fw25wvpgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-left-small-outline" /></template>
