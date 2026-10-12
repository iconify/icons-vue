<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8mn3cssj.css';
import '../../css/b/bcaaafv4h.css';
import '../../css/z/z8-thgb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u8mn3cssj"/><path class="bcaaafv4h"/><path class="z8-thgb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladybird-20-bold" /></template>
