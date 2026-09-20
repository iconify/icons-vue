<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6hs4ob5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6hs4ob5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:constitute-filled" /></template>
