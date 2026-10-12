<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upt8xbe-t.css';
import '../../css/u/uwmcnls3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upt8xbe-t"/><path class="uwmcnls3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copy-check-filled" /></template>
