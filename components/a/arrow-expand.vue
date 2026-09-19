<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/farv-6boo.css';
import '../../css/e/eqvtu_rht.css';
import '../../css/o/orqmh4n-s.css';
import '../../css/d/dn65s6b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="farv-6boo"/><path class="eqvtu_rht"/><path class="orqmh4n-s"/><path class="dn65s6b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-expand" /></template>
