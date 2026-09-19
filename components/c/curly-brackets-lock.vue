<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4z2qobvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o4z2qobvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:curly-brackets-lock" /></template>
