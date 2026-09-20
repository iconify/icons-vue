<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edgfoab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-inactive-outline" /></template>
<style>
.edgfoab5e {
  fill: currentColor;
  d: path("m14 12.996l-1-1V9H9.985l-1-1H13V4h-.615q-.413 0-.707-.294T11.385 3H14zm4.262 8.527L16.4 19.662q-.063.934-.735 1.598q-.673.663-1.665.663q-.975 0-1.612-.61T11.642 20H7.616q-.691 0-1.153-.462T6 18.384V9.616q0-.064.014-.154t.044-.143L1.938 5.2l.708-.708L18.97 20.816zM8.5 19v-7.227l-1.5-1.5v8.112q0 .269.173.442t.443.173zm6.594 1.594q.444-.444.444-1.094t-.444-1.094T14 17.962t-1.094.444t-.444 1.094t.444 1.094t1.094.444t1.094-.444M9.5 19h2.161q.068-.523.46-1.009t.879-.633v-1.085l-3.5-3.5zm-1 0v-7.227zm1 0v-6.227zm4.5.5");
}

</style>
