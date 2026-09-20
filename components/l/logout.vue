<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/v/vlsv6c.css';
import '../../css/l/lo--7m.css';
import '../../css/x/xx5a5k.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c vlsv6c"/><path class="a0m25c lo--7m"/><path class="a0m25c xx5a5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:logout" /></template>
