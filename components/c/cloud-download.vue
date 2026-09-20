<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb-jqrpzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb-jqrpzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-download" /></template>
