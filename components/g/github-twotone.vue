<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlrnvt.css';
import '../../css/a/a0m25c.css';
import '../../css/b/bmu-7y.css';
import '../../css/l/l48m1g.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-32.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrnvt"/><path class="a0m25c bmu-7y"/><path class="a0m25c l48m1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:github-twotone" /></template>
