<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lka1tphse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-account-outline-sharp" /></template>
<style>
.lka1tphse {
  fill: currentColor;
  d: path("M16.539 20.135L13 18.067v-4.11l3.539-2.067l3.576 2.068v4.103zm-2.197-5.977l2.216 1.279l2.215-1.28l-2.215-1.272zm2.658 4.7l2.23-1.281v-2.73L17 16.19zm-3.116-1.281l2.231 1.306v-2.667l-2.23-1.325zm-6.007-7.07Q7 9.632 7 8.386t.877-2.123T10 5.386t2.123.877T13 8.385t-.877 2.123t-2.123.877t-2.123-.877M3 18.616v-1.647q0-.69.348-1.194t.983-.802q1.217-.592 2.51-.975q1.292-.382 3.159-.382h.235q.092 0 .223.011q-.104.258-.165.505l-.116.484H10q-1.679 0-2.928.344t-2.264.89q-.456.24-.632.504q-.176.263-.176.615v.647h6.3q.073.236.179.508t.233.492zm8.413-8.819Q12 9.21 12 8.385t-.587-1.413T10 6.385t-1.412.587T8 8.385t.588 1.412t1.412.588t1.413-.588M10.3 17.616");
}

</style>
