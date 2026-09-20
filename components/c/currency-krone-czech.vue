<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf2llrb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf2llrb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-krone-czech" /></template>
