<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdv-jqbkl.css';
import '../../css/b/btgxzabzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdv-jqbkl"/><path class="btgxzabzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-transfusion-bag" /></template>
