<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0-bq5bbi.css';
import '../../css/r/r_ni-0b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0-bq5bbi"/><path clip-rule="evenodd" class="r_ni-0b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ad-filled" /></template>
