<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge_mu3bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge_mu3bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-check" /></template>
