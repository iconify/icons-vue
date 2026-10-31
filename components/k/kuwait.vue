<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ephwb-o.css';
import '../../css/g/gk5dn-bts.css';
import '../../css/r/r6ariacwh.css';
import '../../css/z/z00sw9avu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="gk5dn-bts"/><path class="r6ariacwh"/><path class="z00sw9avu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:kuwait" /></template>
