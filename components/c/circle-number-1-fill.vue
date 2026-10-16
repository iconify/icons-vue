<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9dvf2alz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9dvf2alz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-1-fill" /></template>
