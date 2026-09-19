<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyk4aoyft.css';
import '../../css/a/a24z59vtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iyk4aoyft"/><path class="a24z59vtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-ltr-fill-16" /></template>
