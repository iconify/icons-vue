<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzjuj_b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzjuj_b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:input-search" /></template>
