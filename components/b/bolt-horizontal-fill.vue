<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v39xsegar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v39xsegar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-horizontal-fill" /></template>
