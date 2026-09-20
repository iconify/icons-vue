<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu9zoybjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:beenhere-outline-rounded" /></template>
<style>
.fu9zoybjh {
  fill: currentColor;
  d: path("M11.49 21.285q-.242-.081-.46-.243l-5.384-4.038q-.298-.218-.472-.566T5 15.713V4.616q0-.691.463-1.153T6.616 3h10.769q.69 0 1.153.463T19 4.616v11.096q0 .379-.174.727t-.472.565l-5.385 4.038q-.217.162-.46.243q-.242.08-.509.08t-.51-.08m.145-1.054q.154.134.365.134t.366-.134l5.384-4.039q.116-.096.183-.22t.067-.28V4.616q0-.231-.192-.424T17.384 4H6.616q-.231 0-.424.192T6 4.615v11.077q0 .154.067.28t.183.22zm-.685-7.35l-1.784-1.785q-.147-.146-.345-.153t-.363.153q-.166.165-.168.357t.162.357l1.933 1.932q.242.242.565.242t.566-.242l4.038-4.038q.146-.146.153-.345t-.153-.363q-.165-.165-.357-.168t-.356.162zM11.635 4H6h12z");
}

</style>
