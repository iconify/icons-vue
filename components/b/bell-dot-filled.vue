<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np7jut26l.css';
import '../../css/p/p_hkdzbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np7jut26l"/><path class="p_hkdzbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-dot-filled" /></template>
