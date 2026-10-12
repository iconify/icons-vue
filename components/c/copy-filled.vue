<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apx8rdbbn.css';
import '../../css/u/uwmcnls3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apx8rdbbn"/><path class="uwmcnls3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copy-filled" /></template>
