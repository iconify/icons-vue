<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfyww_bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfyww_bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-m-filled" /></template>
