<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoxpwbb0y.css';
import '../../css/b/b1-hh0bot.css';
import '../../css/s/s2otf6w0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoxpwbb0y"/><path clip-rule="evenodd" class="b1-hh0bot"/><path class="s2otf6w0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-plus-filled" /></template>
