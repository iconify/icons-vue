<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w_uybke.css';
import '../../css/k/ktwithbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path clip-rule="evenodd" class="ktwithbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-medicine-bold-duotone" /></template>
