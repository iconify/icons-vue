<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnm57cc3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lnm57cc3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bone" /></template>
