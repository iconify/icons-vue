<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f_vnfe55m"/><path class="xxg39pb3b"/><path class="ho_qssbvr"/><path class="hy6idbclh"/><path class="szp2umb0v"/><path class="i8hkus8zu"/><path class="e2h2dib1o"/><path class="ni_yfu75n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:duck" /></template>
<style>
.e2h2dib1o {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M12.502 16.625c.044.625.506 1.511.506 1.511c-1.016 1.474-5.643 3.017-7.354 2.93a7.7 7.7 0 0 1 .627-2.097c1.844-.471 4.661-1.071 6.221-2.344");
}

.f_vnfe55m {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M12.75 17.75c1.226 2.195 1.856-1.361 9.312-2.625s13.729 4.454 13.859 5.413c.132.958-4.447 9.462-9.462 9.462H10.75c-4.143 0-7.022-7.224-4-11.438c0 0 4.5-3.5 6-.812");
}

.ho_qssbvr {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M20.062 22.75c6.672-2.682 15.729-3.171 15.859-2.212c.132.958-4.447 9.462-9.462 9.462H11.813c-4.143 0 1.232-4.429 8.249-7.25");
}

.hy6idbclh {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M25.359 21.125c6-1.312 10.468-1.282 10.563-.587c.079.578-1.559 3.907-3.973 6.454c2.204-2.804 1.42-6.113-6.59-5.867");
}

.i8hkus8zu {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M1.893 9.045c.568-1.1.549.106 3.352.142c1.554.021 1.463-.56 1.664-1.621c.041-.223.776 1.616 2.061 1.807c3.554.531 1.879 1.94 0 2.261c-.901.154-2.01.318-3.938.155c-2.519-.212-3.768-1.528-3.139-2.744");
}

.ni_yfu75n {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M11.708 6.151a1.296 1.296 0 1 1-2.591 0a1.296 1.296 0 0 1 2.591 0");
}

.szp2umb0v {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M7.125 6.125c1.562-4.938 10.44-4.143 10.062.688c-.378 4.829-6.453 7.859-4.179 11.323c-1.586 1.38-5.016.913-6.727.833a156 156 0 0 1 1.812-3.406c2.916-5.235-2.131-5.764-.968-9.438");
}

.xxg39pb3b {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M13.008 18.136C8.02 25.073 6.969 30 10.75 30c-4.143 0-6.578-6.188-4.468-11.031c.463-1.064 1.758-2.492 1.758-2.492l4.179-.008c.162.32.599 1.365.789 1.667");
}

</style>
