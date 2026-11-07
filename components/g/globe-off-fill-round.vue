<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pebqdlbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-fill-round" /></template>
<style>
.pebqdlbzp {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-2.964-2.963a10 10 0 0 1-3.153 1.741c.595-1.143.969-2.397 1.242-3.653L14.7 16.114a20 20 0 0 1-.483 2.293c-.241.868-.547 1.738-1.015 2.513c-.218.361-.721 1.08-1.202 1.08c-.319 0-.607-.293-.799-.516c-.5-.581-.829-1.328-1.09-2.046c-.388-1.068-.636-2.184-.808-3.306A26 26 0 0 1 9.017 13h2.569l-2-2h-.569q.01-.273.023-.546L7.187 8.602A29 29 0 0 0 7.016 11H2.049a10 10 0 0 1 2.207-5.329L1.293 2.707a.999.999 0 1 1 1.414-1.414m6.169 3.34L7.374 3.131a10.004 10.004 0 0 1 13.495 13.495ZM7.015 13c.062 1.953.296 3.937.808 5.826c.247.911.564 1.82 1 2.659A10.03 10.03 0 0 1 2.049 13Z");
}

</style>
