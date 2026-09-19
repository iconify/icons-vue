<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnul7o5fb.css';
import '../../css/p/pr_1mzb5o.css';
import '../../css/l/lxli7kbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnul7o5fb"/><circle class="pr_1mzb5o"/><path class="lxli7kbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-hyper-protect-crypto-services" /></template>
