<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii82hnrhg.css';
import '../../css/e/eu4o_3evy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path clip-rule="evenodd" class="eu4o_3evy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-bolt-2" /></template>
