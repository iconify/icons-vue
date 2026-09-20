<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqbbxr58n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cqbbxr58n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:id-card-solid" /></template>
