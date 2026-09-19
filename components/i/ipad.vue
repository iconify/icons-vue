<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq_ba2bfa.css';
import '../../css/a/ahe_qiacf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="iq_ba2bfa"/><path clip-rule="evenodd" class="ahe_qiacf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:ipad" /></template>
