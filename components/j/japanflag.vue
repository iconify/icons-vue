<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at07s5byk.css';
import '../../css/n/n3ikn2b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at07s5byk"/><circle class="n3ikn2b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:japanflag" /></template>
