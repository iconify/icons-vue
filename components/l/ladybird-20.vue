<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2833rb_h.css';
import '../../css/m/mwapz_r-l.css';
import '../../css/r/rxcdkqb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z2833rb_h"/><path class="mwapz_r-l"/><path class="rxcdkqb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladybird-20" /></template>
