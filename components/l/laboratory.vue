<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k19k3sbft.css';
import '../../css/v/v2uff_sgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k19k3sbft"/><path class="v2uff_sgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:laboratory" /></template>
