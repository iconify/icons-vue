<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv77gccpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-bolt-outline-sharp" /></template>
<style>
.dv77gccpo {
  fill: currentColor;
  d: path("M1 18V6h17.05l-1.6 2H3v8h12.825l-.375 2zm2-2V8zm14.675 1l.7-4H15l4.8-6h.525l-.7 4H23l-4.8 6z");
}

</style>
