<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0ca_zb6s.css';
import '../../css/u/uc5o1eb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="uc5o1eb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:eye-filled" /></template>
