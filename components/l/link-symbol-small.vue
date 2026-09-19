<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kywr9abkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kywr9abkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:link-symbol-small" /></template>
