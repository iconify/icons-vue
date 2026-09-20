<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_spac3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac_spac3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-apple" /></template>
