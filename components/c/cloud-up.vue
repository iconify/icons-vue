<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/q/qjmzsy.css';
import '../../css/c/cn_flp.css';
import '../../css/z/z1niil.css';
import '../../css/a/agm2oc.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c qjmzsy"/><path class="a0m25c cn_flp"/><path class="a0m25c z1niil"/><path class="a0m25c agm2oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-up" /></template>
