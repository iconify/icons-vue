<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjf7a61ga.css';
import '../../css/n/n-mc4deaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjf7a61ga"/><path class="n-mc4deaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aviato-dark" /></template>
