<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks4cp4bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ks4cp4bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:face-neutral" /></template>
