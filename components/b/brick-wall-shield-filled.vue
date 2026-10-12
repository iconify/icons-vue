<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4a0pfb5b.css';
import '../../css/y/y_elplb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4a0pfb5b"/><path clip-rule="evenodd" class="y_elplb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brick-wall-shield-filled" /></template>
