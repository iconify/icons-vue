<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz-wu_ira.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kz-wu_ira"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:link-remove-outline" /></template>
