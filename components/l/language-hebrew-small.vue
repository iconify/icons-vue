<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfe39lxep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lfe39lxep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hebrew-small" /></template>
