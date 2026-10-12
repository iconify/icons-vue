<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixtz2ice.css';
import '../../css/y/yo5kbeb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cixtz2ice"/><path class="yo5kbeb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-backup-filled" /></template>
