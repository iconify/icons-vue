<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkgc78lzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:award-envelope" /></template>
<style>
.bkgc78lzx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.362 4.233l-.162-.368v-.001q-.346-.782-1.2-.782t-1.2.783l-.162.367q-.177.4-.612.444l-.401.041q-.85.088-1.113.901q-.264.812.372 1.381l.3.269q.326.291.234.718l-.085.392q-.182.836.511 1.339q.692.504 1.431.073l.347-.202q.378-.22.756 0l.347.202q.739.431 1.431-.073q.693-.503.511-1.339l-.085-.392q-.092-.427.235-.719L15.115 7q.637-.57.373-1.382q-.263-.813-1.114-.901l-.401-.041q-.434-.044-.611-.443m-9.642 8.55Q4.896 11.75 6.5 11.75h11q1.604 0 2.78 1.033q-.068.021-.131.054L12 17.151l-8.149-4.314q-.063-.033-.131-.054m-.89 1.054q-.58.961-.58 2.163v2q0 1.76 1.245 3.005T6.5 22.25h11q1.76 0 3.005-1.245T21.75 18v-2q0-1.202-.58-2.163q-.108.214-.319.326l-8.5 4.5q-.081.043-.17.065T12 18.75t-.181-.022t-.17-.065l-8.5-4.5q-.211-.112-.319-.326");
}

</style>
