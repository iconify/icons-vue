<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amr6prbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amr6prbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-share" /></template>
