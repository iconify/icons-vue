<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krtu8nbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krtu8nbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-double-nw-se" /></template>
