<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rvnj0gg6v.css';
import '../../css/j/js8mytioh.css';
import '../../css/t/t-7jnmeji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rvnj0gg6v"/><path class="js8mytioh"/><path class="t-7jnmeji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-2-duotone" /></template>
