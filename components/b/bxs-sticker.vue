<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui62x8afp.css';
import '../../css/z/za24chbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui62x8afp"/><path class="za24chbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-sticker" /></template>
