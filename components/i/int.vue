<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jnjvut6nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:int" /></template>
<style>
.jnjvut6nz {
  fill: var(--svg-color--da1b28, #da1b28);
  fill-rule: evenodd;
  d: path("M12 3L6.938 5.503L12 8.063l5.063-2.56zM9.187 7.303v5.411L7.5 14.33l1.687 1.592V21h5.626v-5.08l1.687-1.59l-1.687-1.367v-5.66L12 10.06zm5.063 9.107v4.072h-4.5zm0-7.718L8.4 14.29h-.006l.535.602v-.405l.821-.703v5.923l5.878-5.417l-.596-.59v.444l-.782.675zm-4.5.04v3.515l1.693-1.648zM12 3.552L8.051 5.496l3.95 1.992l3.953-1.992z");
}

</style>
