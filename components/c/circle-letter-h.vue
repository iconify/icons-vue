<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evjbvge6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="evjbvge6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-h" /></template>
