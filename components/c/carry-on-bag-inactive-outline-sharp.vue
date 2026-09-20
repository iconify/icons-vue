<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p99i7ubyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-inactive-outline-sharp" /></template>
<style>
.p99i7ubyl {
  fill: currentColor;
  d: path("m14 12.996l-1-1V9H9.985l-1-1H13V4h-1.616V3H14zm4.262 8.527L16.4 19.662q-.063.934-.735 1.598q-.673.663-1.665.663q-.975 0-1.612-.61T11.642 20H6V9.616q0-.064.014-.154t.044-.143L1.938 5.2l.708-.708L18.97 20.816zM8.5 19v-7.227l-1.5-1.5V19zm6.594 1.594q.444-.444.444-1.094t-.444-1.094T14 17.962t-1.094.444t-.444 1.094t.444 1.094t1.094.444t1.094-.444M9.5 19h2.161q.068-.523.46-1.009t.879-.633v-1.085l-3.5-3.5zm-1 0v-7.227zm1 0v-6.227zm4.5.5");
}

</style>
