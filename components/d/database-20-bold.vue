<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldi2fgv9s.css';
import '../../css/l/li4k_5b9n.css';
import '../../css/d/de_fa463w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ldi2fgv9s"/><path class="li4k_5b9n"/><path class="de_fa463w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:database-20-bold" /></template>
