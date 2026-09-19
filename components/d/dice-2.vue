<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5kaqn3pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x5kaqn3pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:dice-2" /></template>
