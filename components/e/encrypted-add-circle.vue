<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g92rv8l8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:encrypted-add-circle" /></template>
<style>
.g92rv8l8w {
  fill: currentColor;
  d: path("M12 8.52q-.613 0-1.037.433q-.424.434-.424 1.047t.424 1.038T12 11.46q.217 0 .406-.067t.348-.221q.092-.087.19-.158q.098-.073.214-.13q.17-.195.247-.411T13.48 10q0-.614-.434-1.047q-.433-.434-1.047-.434M16.616 19.5h.769v-2.116H19.5v-.769h-2.116V14.5h-.769v2.116H14.5v.769h2.116zM17 21q-1.671 0-2.835-1.164Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21m-5-.039q-3.014-.894-5.007-3.65T5 11.1V5.692l7-2.615l7 2.615v5.656q-.42-.171-.962-.26T17 11q-2.496 0-4.248 1.752T11 17q0 1.03.347 2.011t1.036 1.81l-.192.07z");
}

</style>
