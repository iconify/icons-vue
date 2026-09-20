<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbjt7ebfi.css';
import '../../css/j/jhxqmf5zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbjt7ebfi"/><path class="jhxqmf5zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:inbox-duotone" /></template>
