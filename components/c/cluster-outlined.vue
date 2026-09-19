<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3dfvwb-v.css';
import '../../css/j/jv9nyta4d.css';
import '../../css/l/lrno47b8v.css';
import '../../css/k/k-gcz4-we.css';
import '../../css/b/b0iml815k.css';
import '../../css/c/cvw_2kbed.css';
import '../../css/b/bcf0lotxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3dfvwb-v"/><path class="jv9nyta4d"/><circle class="lrno47b8v"/><circle class="k-gcz4-we"/><path class="b0iml815k"/><circle class="cvw_2kbed"/><circle class="bcf0lotxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cluster-outlined" /></template>
