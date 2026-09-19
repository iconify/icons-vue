<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1712w5xs.css';
import '../../css/d/dbl1jubiy.css';
import '../../css/i/iq0du-zgw.css';
import '../../css/t/tsbi9cmqg.css';
import '../../css/i/ibmjo0bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1712w5xs"/><path class="dbl1jubiy"/><path class="iq0du-zgw"/><path class="tsbi9cmqg"/><path class="ibmjo0bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:feedback" /></template>
