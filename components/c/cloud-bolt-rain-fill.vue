<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ui875ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k9ui875ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-bolt-rain-fill" /></template>
