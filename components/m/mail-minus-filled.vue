<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9hctvb0f.css';
import '../../css/b/blymy14mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9hctvb0f"/><path class="blymy14mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-minus-filled" /></template>
