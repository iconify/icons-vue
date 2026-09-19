<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q31__zbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1789,"height":1000};
const content = `<path class="q31__zbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-beer" /></template>
