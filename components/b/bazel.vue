<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzc3wz_ne.css';
import '../../css/n/n4bn5wd3v.css';
import '../../css/a/ar-ly0b3a.css';
import '../../css/f/fqpmvkjsn.css';
import '../../css/w/w7mw4keuv.css';
import '../../css/a/awae11bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gzc3wz_ne"/><path class="n4bn5wd3v"/><path class="ar-ly0b3a"/><path class="fqpmvkjsn"/><path class="w7mw4keuv"/><path class="awae11bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bazel" /></template>
