<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mscfj9vem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mscfj9vem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fish-bone" /></template>
