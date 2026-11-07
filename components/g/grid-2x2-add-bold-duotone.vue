<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ogxjm1y.css';
import '../../css/b/b5ybc4bew.css';
import '../../css/p/p8bolj64l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5ogxjm1y"/><path class="b5ybc4bew"/><path class="p8bolj64l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-add-bold-duotone" /></template>
