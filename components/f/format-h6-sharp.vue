<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieiy01usf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h6-sharp" /></template>
<style>
.ieiy01usf {
  fill: currentColor;
  d: path("M4 16.5v-9h1v4h5v-4h1v9h-1v-4H5v4zm10.616 0q-.667 0-1.141-.475T13 14.886v-5.77q0-.666.475-1.14t1.14-.475H20v1h-5.384q-.27 0-.443.173T14 9.116V11.5h4.385q.666 0 1.14.475t.475 1.14v1.77q0 .666-.475 1.14t-1.14.475zm-.616-4v2.385q0 .269.173.442t.443.173h3.769q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173z");
}

</style>
