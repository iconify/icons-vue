<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz7xlfb-v.css';
import '../../css/b/bbq8uabvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7xlfb-v"/><path class="bbq8uabvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-zap-filled" /></template>
