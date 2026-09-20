<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfyo9m4in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfyo9m4in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-mongodb" /></template>
