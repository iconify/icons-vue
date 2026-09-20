<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpw-ywx9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flatware-outline-rounded" /></template>
<style>
.kpw-ywx9m {
  fill: currentColor;
  d: path("M5.951 20.356q-.143-.143-.143-.356v-9.384q-.806-.039-1.365-.578t-.558-1.346V3.931q0-.185.123-.308t.308-.123t.307.123t.123.308V7.5h1.131V3.93q0-.184.123-.307t.308-.123t.308.123t.123.308V7.5h1.13V3.93q0-.184.123-.307q.124-.123.308-.123t.308.123q.123.123.123.308v4.761q0 .806-.559 1.346q-.558.539-1.364.578V20q0 .213-.144.356t-.357.144t-.356-.144m6.615 0q-.143-.144-.143-.356v-9.408q-.992-.461-1.496-1.418T10.423 7.1q0-1.383.634-2.492T12.923 3.5t1.867 1.109q.633 1.108.633 2.491q0 1.117-.504 2.074t-1.496 1.418V20q0 .213-.144.356q-.144.144-.357.144t-.356-.144m4.924 0q-.144-.144-.144-.356V4.483q0-.295.183-.494t.465-.199q.76 0 1.44.912q.681.911.681 2.298v4.692q0 .343-.232.576t-.575.232h-.962V20q0 .213-.144.356t-.357.144t-.355-.144");
}

</style>
