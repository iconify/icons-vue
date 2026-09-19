<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwe13cc8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nwe13cc8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:anchor-small" /></template>
