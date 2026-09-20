<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="cm1oe6iah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:framer" /></template>
<style>
.cm1oe6iah {
  d: path("M0 0h256v128H128zm0 128h128l128 128H128v128L0 256z");
}

</style>
