<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx9ihcclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-arrow-right-24-regular" /></template>
<style>
.zx9ihcclz {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-13 5.75a1.75 1.75 0 0 0 1.606 1.744l.144.006h5.065a6.4 6.4 0 0 0 .71 1.5H6.25a3.25 3.25 0 0 1-3.245-3.065L3 17.75V9.372a2.25 2.25 0 0 0 1.5 0zm13.854-3.104a.5.5 0 1 0-.707.707L19.293 17H14.5a.5.5 0 0 0 0 1h4.793l-1.646 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707zm-5.545-1.643c-.426.444-.79.949-1.077 1.5H8.748a.75.75 0 0 1-.102-1.493l.102-.007zM17.75 3a3.25 3.25 0 0 1 3.245 3.065L21 6.25v5.774a6.5 6.5 0 0 0-1.5-.71V6.25a1.75 1.75 0 0 0-1.606-1.744L17.75 4.5H6.25c-.6 0-1.13.302-1.445.763a2.23 2.23 0 0 0-1.581-.201a3.25 3.25 0 0 1 2.841-2.057L6.25 3zm-2.498 6.496a.75.75 0 0 1 .102 1.493l-.102.007H8.748a.75.75 0 0 1-.102-1.493l.102-.007zM3.75 6a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
