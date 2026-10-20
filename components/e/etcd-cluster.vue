<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/h/hjh85ib3l.css';
import '../../css/d/d5xicrbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="hjh85ib3l"/><path class="d5xicrbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="k8s:etcd-cluster" /></template>
