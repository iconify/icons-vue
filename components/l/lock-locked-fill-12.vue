<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r30t8djrj.css';
import '../../css/b/b-ejs9bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r30t8djrj"/><rect class="b-ejs9bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-locked-fill-12" /></template>
