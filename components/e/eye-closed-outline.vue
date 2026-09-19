<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/affnekbuy.css';
import '../../css/w/wd3gak68y.css';
import '../../css/x/xu1bf4b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="affnekbuy"/><path class="wd3gak68y"/><path class="xu1bf4b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:eye-closed-outline" /></template>
