<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ret1j0k_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ret1j0k_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-chevrons-down-filled" /></template>
