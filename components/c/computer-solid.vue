<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8i80_bea.css';
import '../../css/u/uul7rng0w.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 p8i80_bea"/><path class="clr-i-solid clr-i-solid-path-2 uul7rng0w"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:computer-solid" /></template>
