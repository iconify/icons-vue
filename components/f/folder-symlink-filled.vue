<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrt4_oljn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrt4_oljn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-symlink-filled" /></template>
