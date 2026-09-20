<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om1e7y6-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="om1e7y6-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:flag-alt" /></template>
