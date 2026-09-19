<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if7zwef8z.css';
import '../../css/b/bth-2hbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if7zwef8z"/><path class="bth-2hbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:edit" /></template>
