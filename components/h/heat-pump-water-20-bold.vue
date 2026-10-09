<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs_q2h7oe.css';
import '../../css/p/pk1wthwad.css';
import '../../css/b/broi4tbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs_q2h7oe"/><path class="pk1wthwad"/><path class="broi4tbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-water-20-bold" /></template>
